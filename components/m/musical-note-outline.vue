<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjry3wxkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjry3wxkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:musical-note-outline" /></template>
