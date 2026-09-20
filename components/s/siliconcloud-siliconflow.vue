<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp6hm53bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tp6hm53bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:siliconcloud-siliconflow" /></template>
