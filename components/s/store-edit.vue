<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5t501gxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5t501gxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-edit" /></template>
