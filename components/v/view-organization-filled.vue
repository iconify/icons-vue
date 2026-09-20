<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/der5ev0pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="der5ev0pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-organization-filled" /></template>
