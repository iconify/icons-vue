<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc_8i2kot.css';
import '../../css/c/cljz3cbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mc_8i2kot"/><path clip-rule="evenodd" class="cljz3cbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:server-16-solid" /></template>
