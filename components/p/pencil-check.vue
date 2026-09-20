<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8j_b5bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8j_b5bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-check" /></template>
