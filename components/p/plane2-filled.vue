<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcej34bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcej34bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plane2-filled" /></template>
