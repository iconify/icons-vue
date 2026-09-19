<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgyph7b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zgyph7b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-thai-latin" /></template>
