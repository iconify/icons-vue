<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59djne8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z59djne8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:upload" /></template>
