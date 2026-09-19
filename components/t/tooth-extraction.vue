<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n70inkywq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n70inkywq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-extraction" /></template>
