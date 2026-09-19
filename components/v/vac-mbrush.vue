<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4elz8biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4elz8biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vac-mbrush" /></template>
