<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lydelx6ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lydelx6ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-outgoing-line" /></template>
