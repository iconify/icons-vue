<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oix55f0zb.css';
import '../../css/z/zpidxlb0a.css';
import '../../css/i/ivx8nobtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oix55f0zb"/><path class="zpidxlb0a"/><path class="ivx8nobtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offset-20" /></template>
