<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf5oxvb8k.css';
import '../../css/z/zjz25chpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xf5oxvb8k"/><path class="zjz25chpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-missed-20" /></template>
