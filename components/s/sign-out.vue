<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea3l3ebac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1280};
const content = `<path class="ea3l3ebac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sign-out" /></template>
