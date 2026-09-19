<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5p2qw7vu.css';
import '../../css/c/ci51xnbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5p2qw7vu"/><path class="ci51xnbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:speaker" /></template>
