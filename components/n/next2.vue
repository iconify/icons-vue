<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf5pf_opx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lf5pf_opx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:next2" /></template>
