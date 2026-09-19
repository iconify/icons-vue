<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb5anbcmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qb5anbcmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:messenger" /></template>
