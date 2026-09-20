<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f012qlbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f012qlbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wappalyzer" /></template>
