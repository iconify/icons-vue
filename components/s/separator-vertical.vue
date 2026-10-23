<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkbkddc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkbkddc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:separator-vertical" /></template>
