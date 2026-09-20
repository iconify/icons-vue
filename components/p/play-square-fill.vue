<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-2la_f4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-2la_f4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:play-square-fill" /></template>
