<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru5z-ccmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5z-ccmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:meh-alt" /></template>
