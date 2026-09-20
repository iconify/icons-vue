<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihb7gccby.css';
import '../../css/z/zau8vgbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihb7gccby"/><path class="zau8vgbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:power-supply-plug" /></template>
