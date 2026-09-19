<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsg5j7ibl.css';
import '../../css/h/ht4s8t-7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="ht4s8t-7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-forward-circle-outline" /></template>
