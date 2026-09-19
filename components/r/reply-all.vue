<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwds4g5lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mwds4g5lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:reply-all" /></template>
