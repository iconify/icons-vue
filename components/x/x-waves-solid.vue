<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxy4-fu0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxy4-fu0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-waves-solid" /></template>
