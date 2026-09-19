<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sje9hqxyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sje9hqxyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag-arrow-up" /></template>
