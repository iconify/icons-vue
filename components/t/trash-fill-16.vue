<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvpwvr8sq.css';
import '../../css/t/tgfroo5dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qvpwvr8sq"/><path class="tgfroo5dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:trash-fill-16" /></template>
