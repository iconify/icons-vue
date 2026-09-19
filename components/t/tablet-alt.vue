<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvd82_bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="xvd82_bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tablet-alt" /></template>
