<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsgj5pbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsgj5pbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:voice-circled" /></template>
