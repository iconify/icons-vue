<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjv-qyyht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjv-qyyht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-down-sharp-fill" /></template>
