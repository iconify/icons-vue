<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj062-b3v.css';
import '../../css/l/lgz6trbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj062-b3v"/><path class="lgz6trbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:yoga-back-stretch-1-bold" /></template>
