<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxp1t4b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxp1t4b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:workspace-import" /></template>
