<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecr8r-six.css';
import '../../css/i/ibldiexph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ecr8r-six"/><path class="ibldiexph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-box" /></template>
