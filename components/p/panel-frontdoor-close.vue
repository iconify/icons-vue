<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo2b0jzxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo2b0jzxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-frontdoor-close" /></template>
