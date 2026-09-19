<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psrz9t_gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psrz9t_gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:square-help" /></template>
