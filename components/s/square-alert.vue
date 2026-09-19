<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk6ttvbnd.css';
import '../../css/q/qx6xq3b3x.css';
import '../../css/p/pp6vxiujp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk6ttvbnd"/><path class="qx6xq3b3x"/><circle class="pp6vxiujp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-alert" /></template>
