<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhj__jb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhj__jb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-2-line" /></template>
