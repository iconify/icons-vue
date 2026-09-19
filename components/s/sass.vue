<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvr2oubro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="xvr2oubro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sass" /></template>
