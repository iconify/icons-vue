<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsv0algms.css';
import '../../css/i/i3h9pj49l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hsv0algms"/><path clip-rule="evenodd" class="i3h9pj49l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tape-16" /></template>
