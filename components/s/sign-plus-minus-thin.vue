<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fun39o8tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fun39o8tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-minus-thin" /></template>
