<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzr5fjb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzr5fjb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-square3-filled" /></template>
