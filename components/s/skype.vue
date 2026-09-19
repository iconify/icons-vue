<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct49_jb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ct49_jb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skype" /></template>
