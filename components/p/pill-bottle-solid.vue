<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9cdaqbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9cdaqbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pill-bottle-solid" /></template>
