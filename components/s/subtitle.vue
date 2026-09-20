<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suh7nhtmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suh7nhtmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:subtitle" /></template>
