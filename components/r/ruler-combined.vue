<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f17ai7b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f17ai7b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ruler-combined" /></template>
