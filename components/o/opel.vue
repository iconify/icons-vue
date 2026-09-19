<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd_vh-osx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd_vh-osx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:opel" /></template>
