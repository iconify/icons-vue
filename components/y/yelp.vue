<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzzypybkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzzypybkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:yelp" /></template>
