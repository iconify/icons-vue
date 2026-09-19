<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm3i78bcl.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/t/tk43u5bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm3i78bcl"/><path class="bwibdw4bb"/><path class="tk43u5bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:smile" /></template>
