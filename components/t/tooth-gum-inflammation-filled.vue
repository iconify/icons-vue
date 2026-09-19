<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt56d1y2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gt56d1y2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-gum-inflammation-filled" /></template>
