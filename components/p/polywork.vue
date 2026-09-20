<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf4d68l2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf4d68l2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:polywork" /></template>
