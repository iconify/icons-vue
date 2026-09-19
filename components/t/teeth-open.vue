<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce5pb3pjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ce5pb3pjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:teeth-open" /></template>
