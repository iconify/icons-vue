<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_x_-kue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_x_-kue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message2-filled" /></template>
