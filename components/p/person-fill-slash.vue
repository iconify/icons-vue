<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn5tnnbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qn5tnnbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-fill-slash" /></template>
