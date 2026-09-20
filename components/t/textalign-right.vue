<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtkf2kbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtkf2kbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-right" /></template>
