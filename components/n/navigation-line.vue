<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdbj31jbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdbj31jbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:navigation-line" /></template>
