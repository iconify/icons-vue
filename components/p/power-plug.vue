<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b69v5bj7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b69v5bj7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:power-plug" /></template>
