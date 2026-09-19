<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz0xrmbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rz0xrmbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-graphics-small-filled" /></template>
