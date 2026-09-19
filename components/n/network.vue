<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwvze54tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwvze54tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:network" /></template>
