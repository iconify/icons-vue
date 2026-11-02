<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy5-_nb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy5-_nb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speaker-fill" /></template>
