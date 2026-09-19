<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1fkrb3h"/><path class="reh5oyj1n"/><path class="z3k3pln4t"/><path class="fl88mcetg"/><path class="hc7jqs4ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-emoji-objects" /></template>
<style>
.dp1fkrb3h {
  fill: currentColor;
  d: path("M10 18h4v1h-4zm0-2h4v1h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.fl88mcetg {
  fill: currentColor;
  d: path("m9.672 9.58l.707-.706l2.122 2.121l-.707.707z");
}

.hc7jqs4ue {
  fill: currentColor;
  d: path("m12.208 11.712l-.707-.707l2.121-2.121l.707.707z");
}

.reh5oyj1n {
  fill: currentColor;
  d: path("M12 3c-.46 0-.93.04-1.4.14c-2.76.53-4.96 2.76-5.48 5.52c-.48 2.61.48 5.01 2.22 6.56c.43.38.66.91.66 1.47V19c0 1.1.9 2 2 2h.28a1.98 1.98 0 0 0 3.44 0H14c1.1 0 2-.9 2-2v-2.31c0-.55.22-1.09.64-1.46A6.96 6.96 0 0 0 19 10c0-3.87-3.13-7-7-7m2 16h-4v-1h4zm0-2h-4v-1h4zm1.31-3.26c-.09.08-.16.18-.24.26H8.92c-.08-.09-.15-.19-.24-.27c-1.32-1.18-1.91-2.94-1.59-4.7c.36-1.94 1.96-3.55 3.89-3.93c.34-.07.68-.1 1.02-.1c2.76 0 5 2.24 5 5c0 1.43-.61 2.79-1.69 3.74");
}

.z3k3pln4t {
  fill: currentColor;
  d: path("M11.5 11h1v3h-1z");
}

</style>
