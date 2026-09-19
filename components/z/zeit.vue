<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8z5tcckk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8z5tcckk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zeit" /></template>
