<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orbkw0iwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="orbkw0iwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:multiply-circle-fill" /></template>
