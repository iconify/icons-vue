<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuybvqbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuybvqbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:trending-up" /></template>
