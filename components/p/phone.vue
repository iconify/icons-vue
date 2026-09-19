<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od73h5bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od73h5bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone" /></template>
