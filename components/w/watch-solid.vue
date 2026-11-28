<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-5x-acls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-5x-acls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:watch-solid" /></template>
