<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c07fxkbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c07fxkbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:medium-signal" /></template>
