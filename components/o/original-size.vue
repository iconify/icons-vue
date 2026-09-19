<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2op35cji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g2op35cji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:original-size" /></template>
