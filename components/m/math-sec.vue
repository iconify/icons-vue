<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr05tub9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr05tub9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-sec" /></template>
