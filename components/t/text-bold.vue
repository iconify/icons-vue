<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8f--c0up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8f--c0up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-bold" /></template>
