<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8kczb8t.css';
import '../../css/c/c-tt48brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ck8kczb8t"/><circle class="c-tt48brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-mentor-rtl" /></template>
