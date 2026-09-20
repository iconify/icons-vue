<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fioatobyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fioatobyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shrink-diagonal-light" /></template>
