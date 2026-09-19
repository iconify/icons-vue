<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey_kr2fcq.css';
import '../../css/f/f8js4o8ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey_kr2fcq"/><path class="f8js4o8ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:train-sharp" /></template>
