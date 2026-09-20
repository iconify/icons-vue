<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk62wsz_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk62wsz_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-minus" /></template>
