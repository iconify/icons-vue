<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmvg7-d7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":470,"height":512};
const content = `<path class="qmvg7-d7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zork" /></template>
