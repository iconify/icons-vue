<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljvs4moct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="ljvs4moct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:night-alt-rain" /></template>
