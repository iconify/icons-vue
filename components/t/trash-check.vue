<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jju9kab-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jju9kab-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trash-check" /></template>
