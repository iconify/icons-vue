<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfzm3g0mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfzm3g0mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:navigation" /></template>
