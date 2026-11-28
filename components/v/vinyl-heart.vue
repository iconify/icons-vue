<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkle8ob3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkle8ob3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:vinyl-heart" /></template>
