<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htjhbbcsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="htjhbbcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tennis-ball" /></template>
