<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on3sloqnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on3sloqnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:package-lock" /></template>
