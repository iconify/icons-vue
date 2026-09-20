<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjodo-bjv.css';
import '../../css/e/ez5ds-_fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjodo-bjv"/><path class="ez5ds-_fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:search-square-fill" /></template>
