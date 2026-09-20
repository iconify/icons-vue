<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eexufrf1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eexufrf1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:send-receive-16" /></template>
