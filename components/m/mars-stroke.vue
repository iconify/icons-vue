<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxd8x6rnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxd8x6rnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mars-stroke" /></template>
