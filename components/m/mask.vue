<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5z2czd5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5z2czd5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:mask" /></template>
