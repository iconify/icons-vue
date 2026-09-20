<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5hk3yb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="g5hk3yb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tower-broadcast-1" /></template>
