<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjjzc_bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ml" /></template>
<style>
.gjjzc_bio {
  fill: var(--svg-color--11967f, #11967f);
  d: path("m3 3l3.6 1.512v15.066L3 21zm4.8 7.2l3.6 1.512v6.066L7.8 19.2zM21 21l-3.6-1.512V4.422L21 3zm-4.8-7.2l-3.6-1.512V6.222L16.2 4.8z");
}

</style>
