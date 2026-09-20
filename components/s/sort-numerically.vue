<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj9gbswqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj9gbswqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:sort-numerically" /></template>
