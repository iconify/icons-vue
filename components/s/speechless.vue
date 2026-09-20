<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0qkxxb-q.css';
import '../../css/u/u0bzg8byf.css';
import '../../css/v/v4-7eu8rv.css';
import '../../css/z/ztmfb6bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="u0qkxxb-q"/><circle class="u0bzg8byf"/><path class="v4-7eu8rv"/><path class="ztmfb6bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:speechless" /></template>
