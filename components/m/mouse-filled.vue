<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy2i2x7fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy2i2x7fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mouse-filled" /></template>
