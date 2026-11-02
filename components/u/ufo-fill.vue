<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npziikbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npziikbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ufo-fill" /></template>
