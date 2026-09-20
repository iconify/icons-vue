<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pykl44r4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pykl44r4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:square-shape" /></template>
