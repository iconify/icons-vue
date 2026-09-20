<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5alxxbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5alxxbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:note-add" /></template>
