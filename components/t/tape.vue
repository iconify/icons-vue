<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hun52_6rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="hun52_6rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tape" /></template>
