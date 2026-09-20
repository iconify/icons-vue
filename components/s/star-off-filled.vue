<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id6xw4bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id6xw4bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-off-filled" /></template>
