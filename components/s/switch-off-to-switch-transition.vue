<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g36zgr.css';
import '../../css/d/dg35tf.css';
import '../../css/c/cx-from-7px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g36zgr"/><circle class="dg35tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch-off-to-switch-transition" /></template>
