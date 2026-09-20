<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqfzebbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqfzebbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play-filled" /></template>
