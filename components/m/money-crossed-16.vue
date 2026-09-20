<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ja28kow.css';
import '../../css/q/q6as41mwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z6ja28kow"/><path clip-rule="evenodd" class="q6as41mwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:money-crossed-16" /></template>
