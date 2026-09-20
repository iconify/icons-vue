<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diz628b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diz628b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-tg" /></template>
