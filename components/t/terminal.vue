<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5_simimr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l5_simimr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:terminal" /></template>
