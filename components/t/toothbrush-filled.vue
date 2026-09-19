<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hio3cobnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hio3cobnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:toothbrush-filled" /></template>
