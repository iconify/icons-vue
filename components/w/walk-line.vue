<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-gm21tca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-gm21tca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:walk-line" /></template>
