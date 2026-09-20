<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9dtcsm4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9dtcsm4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zeromq" /></template>
