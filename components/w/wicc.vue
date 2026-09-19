<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou7zrpb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ou7zrpb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:wicc" /></template>
