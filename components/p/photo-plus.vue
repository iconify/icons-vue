<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fawgp6okp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fawgp6okp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus" /></template>
