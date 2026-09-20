<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axl4_ccxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axl4_ccxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-2-fill" /></template>
