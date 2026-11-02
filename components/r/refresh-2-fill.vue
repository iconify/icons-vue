<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbwjs5bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbwjs5bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-2-fill" /></template>
