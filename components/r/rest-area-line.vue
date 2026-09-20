<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukkc8hbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukkc8hbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rest-area-line" /></template>
