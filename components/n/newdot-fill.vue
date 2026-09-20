<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqfh8rb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqfh8rb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:newdot-fill" /></template>
