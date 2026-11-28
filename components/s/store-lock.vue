<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh2ktmb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh2ktmb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:store-lock" /></template>
