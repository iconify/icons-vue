<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trx77weeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-bulk" /></template>
<style>
.trx77weeh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.199 11.956l-2.501 3.145a1.234 1.234 0 0 1-2.198-.768v-3H3.667a1.322 1.322 0 0 1-1.035-2.144l5.004-6.29a1.232 1.232 0 0 1 2.197.768v3h1.834a1.32 1.32 0 0 1 1.034 2.144Zm7.782-3.152c.284 1.419 1.144 2.54 2.286 3.396a1 1 0 0 1 .107.093C21.65 13.57 22 15.253 22 17c0 1.33-.522 2.597-1.464 3.536a5.004 5.004 0 0 1-7.072 0A5 5 0 0 1 12 17c0-.964.259-2.007.96-2.707a.999.999 0 0 1 1.707.707a.333.333 0 1 0 .666 0c0-.207-.017-.419-.083-.617c-.061-.179-.159-.348-.251-.513a12 12 0 0 1-.227-.423c-1.04-2.082-.078-3.882 1.603-5.228a1.002 1.002 0 0 1 1.606.585");
}

</style>
