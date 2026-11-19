<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uemridbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uemridbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:varial" /></template>
