<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-o0df6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ji-o0df6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-2-fill" /></template>
