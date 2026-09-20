<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krfuj-b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zeta" /></template>
<style>
.krfuj-b3p {
  fill: var(--svg-color--005741, #005741);
  d: path("M16.958 15.917v2.393H7.086c.137-1.575.645-2.683 2.402-4.241l7.47-6.373v5.592h2.69V3H4.355v5.128h2.688V5.69h8.123l-7.433 6.343l-.018.017c-3.115 2.758-3.363 4.984-3.363 7.607V21h15.293v-5.082h-2.689z");
}

</style>
