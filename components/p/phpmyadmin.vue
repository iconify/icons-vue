<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuptj_q1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kuptj_q1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpmyadmin" /></template>
