<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdhjejb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zdhjejb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sad-face-in-circle-outline" /></template>
