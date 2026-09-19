<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxi-gcmxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="jxi-gcmxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:scorp" /></template>
