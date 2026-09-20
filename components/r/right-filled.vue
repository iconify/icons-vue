<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyqc8-t6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pyqc8-t6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:right-filled" /></template>
