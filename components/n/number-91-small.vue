<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrgf5g66q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrgf5g66q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-91-small" /></template>
