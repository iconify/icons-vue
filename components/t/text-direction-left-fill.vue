<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plfbs3b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plfbs3b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-left-fill" /></template>
