<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agn34nbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agn34nbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:speakap" /></template>
