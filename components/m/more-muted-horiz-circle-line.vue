<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i87ligbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i87ligbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-horiz-circle-line" /></template>
