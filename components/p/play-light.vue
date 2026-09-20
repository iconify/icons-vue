<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgi0-jbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgi0-jbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:play-light" /></template>
