<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2xq-t_kz.css';
import '../../css/y/ydi0djeuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2xq-t_kz"/><path class="ydi0djeuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:manifest-dark" /></template>
