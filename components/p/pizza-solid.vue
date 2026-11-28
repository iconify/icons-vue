<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y97h3db-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y97h3db-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pizza-solid" /></template>
