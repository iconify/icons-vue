<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-1qxbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id-1qxbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roll20" /></template>
