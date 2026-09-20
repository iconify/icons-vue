<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1gszqbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y1gszqbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:screen-alt-solid" /></template>
