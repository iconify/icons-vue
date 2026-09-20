<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp1ymwo-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp1ymwo-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:pound" /></template>
