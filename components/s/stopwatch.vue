<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwcoh5b4b.css';
import '../../css/r/r-ls0rn8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwcoh5b4b"/><path class="r-ls0rn8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:stopwatch" /></template>
