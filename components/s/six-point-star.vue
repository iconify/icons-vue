<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df88n9bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="df88n9bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:six-point-star" /></template>
