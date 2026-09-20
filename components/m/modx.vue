<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uueukmy4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uueukmy4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:modx" /></template>
