<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xshk93bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xshk93bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:reddit-fill" /></template>
