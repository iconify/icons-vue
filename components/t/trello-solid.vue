<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh2k2lb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh2k2lb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trello-solid" /></template>
