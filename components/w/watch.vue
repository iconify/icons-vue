<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krn9eiidq.css';
import '../../css/y/ypuxzcc_r.css';
import '../../css/e/e2_x5zb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="krn9eiidq"/><path class="ypuxzcc_r"/><path class="e2_x5zb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:watch" /></template>
