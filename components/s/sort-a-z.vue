<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4pekuvlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4pekuvlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:sort-a-z" /></template>
