<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kfj-p0awy"/><path class="bnrpj5wmy"/><path class="cbypibc_p"/><path class="oclnrcctz"/><path class="u8m0zpbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:watch" /></template>
<style>
.bnrpj5wmy {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M32 18a2 2 0 0 0-2-2h-1a2 2 0 0 0 0 4h1a2 2 0 0 0 2-2");
}

.cbypibc_p {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M6 18c0-6.627 5.373-12 12-12c6.628 0 12 5.373 12 12s-5.372 12-12 12c-6.627 0-12-5.373-12-12");
}

.kfj-p0awy {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M25 32a4 4 0 0 1-4 4h-6a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4z");
}

.oclnrcctz {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M10 18a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.u8m0zpbqw {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M23 22a1 1 0 0 1-.514-.143l-5-3A1 1 0 0 1 17 18v-7a1 1 0 0 1 2 0v6.434l4.516 2.708A1 1 0 0 1 23 22");
}

</style>
