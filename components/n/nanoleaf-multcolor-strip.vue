<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wea-thbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wea-thbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-multcolor-strip" /></template>
