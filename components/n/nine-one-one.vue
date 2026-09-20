<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpy31sbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpy31sbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nine-one-one" /></template>
