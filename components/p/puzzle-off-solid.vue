<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r72p_bckr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r72p_bckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-off-solid" /></template>
