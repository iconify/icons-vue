<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpy5ncbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rpy5ncbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:video-slash" /></template>
