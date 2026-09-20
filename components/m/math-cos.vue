<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hucvy1bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hucvy1bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-cos" /></template>
