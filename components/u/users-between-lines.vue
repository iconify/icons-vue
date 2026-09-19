<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trcf_86qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="trcf_86qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:users-between-lines" /></template>
