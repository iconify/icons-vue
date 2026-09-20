<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw__92b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw__92b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:phone-duotone-line" /></template>
