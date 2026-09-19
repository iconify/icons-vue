<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5zh5c4mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5zh5c4mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:small-long-up" /></template>
