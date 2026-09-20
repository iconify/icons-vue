<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sllvyibzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sllvyibzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sobbing-face-in-circle-outline" /></template>
