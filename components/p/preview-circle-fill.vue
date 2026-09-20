<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxa326maf.css';
import '../../css/r/r7uozib3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxa326maf"/><path class="r7uozib3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:preview-circle-fill" /></template>
