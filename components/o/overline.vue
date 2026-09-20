<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj8o377ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj8o377ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:overline" /></template>
