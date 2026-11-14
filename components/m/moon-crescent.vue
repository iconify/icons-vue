<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uynymvukm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moon-crescent" /></template>
<style>
.uynymvukm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.338 20.608q2.982-2.123 3.888-5.67l.001-.002v-.001q.04-.157.011-.317l-.004-.022q-.022-.103-.071-.196t-.121-.169q-.073-.076-.164-.129t-.193-.079q-.163-.041-.329-.009l-.01.002h-.002q-4.635.973-7.984-2.376T9.984 3.655v-.001q.036-.17-.007-.339q-.026-.1-.077-.19q-.052-.089-.126-.161q-.073-.072-.164-.122q-.09-.049-.191-.073l-.015-.003q-.17-.036-.339.007q-3.549.906-5.673 3.889t-1.82 6.633q.305 3.649 2.894 6.239t6.239 2.894t6.633-1.82m-.87-1.221q-2.536 1.805-5.638 1.546t-5.303-2.46t-2.46-5.303t1.546-5.638q1.459-2.048 3.706-2.944q-.487 4.645 2.98 8.113t8.113 2.98q-.896 2.247-2.944 3.706");
}

</style>
