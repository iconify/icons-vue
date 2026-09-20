<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8e9zabhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8e9zabhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paw-filled" /></template>
