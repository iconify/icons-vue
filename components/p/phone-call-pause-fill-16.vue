<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqn921buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cqn921buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-pause-fill-16" /></template>
