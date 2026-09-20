<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm21li_zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm21li_zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signpost-big" /></template>
