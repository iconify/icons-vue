<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-r4blpba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d-r4blpba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sugarcane-stalk-with-leaves" /></template>
