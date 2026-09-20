<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvslibb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nvslibb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:yen-yuan" /></template>
