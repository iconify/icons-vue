<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6g48wlqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6g48wlqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:user-minus" /></template>
