<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="n2ii7nb-c"/><path class="o8kk9p3nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mm" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.n2ii7nb-c {
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53A8.47 8.47 0 0 0 20.47 12A8.47 8.47 0 0 0 12 3.53A8.47 8.47 0 0 0 3.53 12A8.47 8.47 0 0 0 12 20.47");
}

.o8kk9p3nz {
  d: path("M17.294 7.766v8.47h-.53V9.354l-2.117 2.596v4.286h-4.27l3.74-4.577V9.435l-3.332 4.125l-3.55-4.125v6.801h-.53v-8.47l4.082 4.804l3.86-4.804v3.259zm-3.177 4.83l-2.551 3.11h2.551z");
}

</style>
