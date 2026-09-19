<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7mi3lqpf.css';
import '../../css/n/n5f4dctir.css';
import '../../css/h/hwn9kbc0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="m7mi3lqpf"/><path class="n5f4dctir"/><path class="hwn9kbc0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-center" /></template>
