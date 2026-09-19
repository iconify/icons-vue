<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehxy3fbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":472};
const content = `<path class="ehxy3fbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:play" /></template>
