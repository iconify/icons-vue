<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irlny6bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="irlny6bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:stripe" /></template>
