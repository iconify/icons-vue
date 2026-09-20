<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c07avib5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c07avib5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pendulum" /></template>
