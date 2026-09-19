<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygv58pb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ygv58pb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:skype-check" /></template>
