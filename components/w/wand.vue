<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39id2hno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r39id2hno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wand" /></template>
