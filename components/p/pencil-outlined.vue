<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9m8hylsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9m8hylsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:pencil-outlined" /></template>
