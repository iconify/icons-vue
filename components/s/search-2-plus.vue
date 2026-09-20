<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hof0els4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hof0els4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-plus" /></template>
