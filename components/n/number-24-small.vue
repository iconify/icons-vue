<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1xm83wsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1xm83wsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-24-small" /></template>
