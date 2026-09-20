<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4gxffbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4gxffbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-1-divide-2" /></template>
