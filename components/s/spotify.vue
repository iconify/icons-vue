<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azpaz2bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="azpaz2bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spotify" /></template>
