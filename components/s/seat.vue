<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdhhczbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdhhczbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:seat" /></template>
