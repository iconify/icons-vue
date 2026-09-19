<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sem2f4bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sem2f4bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-then-curving-up-arrow-small-filled" /></template>
