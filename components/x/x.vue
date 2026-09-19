<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wozg3fb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wozg3fb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:x" /></template>
