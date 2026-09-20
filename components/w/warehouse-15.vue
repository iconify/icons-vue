<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si9tr4_ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="si9tr4_ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:warehouse-15" /></template>
