<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z904_qjsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z904_qjsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:planet" /></template>
