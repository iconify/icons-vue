<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldn6wy7kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldn6wy7kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:minimize-alt" /></template>
