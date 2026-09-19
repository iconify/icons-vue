<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kryvvdb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kryvvdb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:traffic-cone" /></template>
