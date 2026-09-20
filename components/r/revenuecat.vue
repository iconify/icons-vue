<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv99-xynx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv99-xynx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:revenuecat" /></template>
