<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjjfaz5bu.css';
import '../../css/b/b93j9cbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mjjfaz5bu"/><path class="b93j9cbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pause-outline" /></template>
