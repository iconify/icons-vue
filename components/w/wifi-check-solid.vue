<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcqkfzbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcqkfzbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-check-solid" /></template>
