<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkn4hp0vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkn4hp0vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:upload" /></template>
