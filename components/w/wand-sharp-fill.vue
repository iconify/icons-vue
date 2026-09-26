<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti-l6oboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp-fill" /></template>
<style>
.ti-l6oboq {
  fill: currentColor;
  d: path("M18.1716 2.2929L21.7071 5.8284C22.0976 6.219 22.0976 6.8521 21.7071 7.2426L18.0749 10.8749L13.1251 5.9251L16.7574 2.2929C17.1479 1.9024 17.781 1.9024 18.1716 2.2929ZM11.7109 7.3393L16.6607 12.2891L7.2426 21.7071C6.8521 22.0976 6.219 22.0976 5.8284 21.7071L2.2929 18.1716C1.9024 17.781 1.9024 17.1479 2.2929 16.7574L11.7109 7.3393Z");
}

</style>
