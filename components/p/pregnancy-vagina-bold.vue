<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za6sec2-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za6sec2-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pregnancy-vagina-bold" /></template>
