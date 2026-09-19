<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bow-_kbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bow-_kbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pandora" /></template>
