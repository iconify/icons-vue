<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="y9r0f22bp"/><path class="o7yl6cc7i"/><path class="bv209ctre"/><path class="ukf3wc_hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:placard" /></template>
<style>
.bv209ctre {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 14h-7a1 1 0 0 1 0-2h7a1 1 0 0 1 0 2m8 0h-4a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2m0-5H10a1 1 0 0 1 0-2h15a1 1 0 1 1 0 2");
}

.o7yl6cc7i {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M28 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h21a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2");
}

.ukf3wc_hc {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M15 21h5v2h-5z");
}

.y9r0f22bp {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M20 33.5v-31A1.5 1.5 0 0 0 18.5 1h-2A1.5 1.5 0 0 0 15 2.5v31a1.5 1.5 0 0 0 1.5 1.5h2a1.5 1.5 0 0 0 1.5-1.5");
}

</style>
