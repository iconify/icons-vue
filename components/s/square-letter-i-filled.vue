<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6k4rbcjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6k4rbcjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-i-filled" /></template>
