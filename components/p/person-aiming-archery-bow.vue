<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npisey23r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="npisey23r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-aiming-archery-bow" /></template>
