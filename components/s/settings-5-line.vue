<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwqurubdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwqurubdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-5-line" /></template>
