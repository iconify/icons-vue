<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrurpboo.css';
import '../../css/v/vmz9b8bgm.css';
import '../../css/j/jjy9cwbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="vmz9b8bgm"/><path class="jjy9cwbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-plus-48" /></template>
