<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2o46fbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2o46fbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-plus-outline" /></template>
