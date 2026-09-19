<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l50o5rb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l50o5rb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sleepy2" /></template>
