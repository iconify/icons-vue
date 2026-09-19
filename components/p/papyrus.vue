<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5q2e8byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5q2e8byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:papyrus" /></template>
