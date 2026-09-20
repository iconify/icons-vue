<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqhi3t3gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqhi3t3gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:traffic-cone-off" /></template>
