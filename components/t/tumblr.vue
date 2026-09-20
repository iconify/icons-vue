<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcuzrxbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcuzrxbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tumblr" /></template>
