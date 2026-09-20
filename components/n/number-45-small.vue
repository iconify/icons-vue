<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt9kp4zrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt9kp4zrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-45-small" /></template>
