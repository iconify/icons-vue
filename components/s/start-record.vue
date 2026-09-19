<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca7z5h1rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7z5h1rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:start-record" /></template>
