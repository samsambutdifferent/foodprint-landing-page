<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Mission</template>
    We want to make it easier for people to eat sustainably. As 26% of GHG comes from food production, our eating habits are essential in combating climate change.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>What we do</template>
    <span style="font-weight: bold;">Measure:</span> select a meal from our pre-populated list or enter the ingredients to a custom meal.
    <span style="font-weight: bold;">Reduce:</span> view a breakdown of CO2e for each ingredient and browse alternatives for the highest emission items.
    <span style="font-weight: bold;">Learn & Offset:</span> understand the equivalent impact compared to other activities and offset your emissions.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Our Approach</template>
    Publicly available data sets. Cross referencing multiple sources. Estimation & Interpolation
  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Why we do it</template>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.
  </WelcomeItem> -->

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
      Email us at <a>malin@mycarbonfoodprint.co.uk</a> to stay in touch
  </WelcomeItem>
</template>
