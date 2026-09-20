<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj7514b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kj7514b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:undo-filled" /></template>
