<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj10p5rzw.css';
import '../../css/b/bmckwmrqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lj10p5rzw"/><path class="bmckwmrqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:open" /></template>
