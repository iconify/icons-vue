<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="l0g9xz9jh"/><path class="gg37k0bgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-fill" /></template>
<style>
.gg37k0bgh {
  d: path("M7.9689 10C8.7286 8.4686 10.2905 7.5 12 7.5C13.7095 7.5 15.2714 8.4686 16.0311 10M12 3.5L12 2M18.0104 5.9896L19.0711 4.9289M5.9896 5.9896L4.9289 4.9289M3.9689 10H2.4689M20.0311 10H21.5311");
}

.l0g9xz9jh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 23L4.0036 23C2.7693 23 1.7931 22.2866 1.3207 21.3423C0.8483 20.398 0.8627 19.189 1.6028 18.2012L4.5997 14.2012C5.1663 13.445 6.0559 13 7.0006 13L16.9994 13C17.9441 13 18.8337 13.445 19.4003 14.2012L22.3972 18.2012C23.1373 19.189 23.1517 20.398 22.6793 21.3423C22.2069 22.2866 21.2307 23 19.9964 23ZM9.2825 21L9.782 19L14.218 19L14.7175 21L16.779 21L16.2795 19L20.4966 19L18.9982 17L15.78 17L15.2805 15L13.219 15L13.7185 17L10.2815 17L10.781 15L8.7195 15L8.22 17L5.0018 17L3.5034 19L7.7205 19L7.221 21Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
