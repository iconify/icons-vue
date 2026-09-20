<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zskhygbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zskhygbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-waters" /></template>
