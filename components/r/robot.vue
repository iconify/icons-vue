<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwirw_v_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rwirw_v_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:robot" /></template>
