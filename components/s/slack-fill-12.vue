<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c916p865d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c916p865d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:slack-fill-12" /></template>
