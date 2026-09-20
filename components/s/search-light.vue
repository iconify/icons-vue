<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npb90acjk.css';
import '../../css/j/jy2_mcanx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npb90acjk"/><path class="jy2_mcanx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-light" /></template>
