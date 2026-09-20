<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh-pk_b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yh-pk_b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:receipt-outline" /></template>
