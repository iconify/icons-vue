<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1gur68if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1gur68if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-11" /></template>
