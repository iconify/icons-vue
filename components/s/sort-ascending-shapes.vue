<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ligmv2brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ligmv2brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-ascending-shapes" /></template>
