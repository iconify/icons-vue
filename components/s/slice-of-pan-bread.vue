<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j83o6di_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j83o6di_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:slice-of-pan-bread" /></template>
