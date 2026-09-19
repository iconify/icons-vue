<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g64z6fbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g64z6fbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:sort" /></template>
