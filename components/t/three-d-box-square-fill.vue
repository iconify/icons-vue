<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkcq33bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkcq33bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:three-d-box-square-fill" /></template>
