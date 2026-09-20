<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgsxmy4fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgsxmy4fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftedge" /></template>
