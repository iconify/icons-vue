<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jog5b1b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jog5b1b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:play-list-remove" /></template>
