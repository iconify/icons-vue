<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5i42c4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oc5i42c4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-leaping-over-hurdle" /></template>
