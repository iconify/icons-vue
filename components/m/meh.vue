<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnsy5qb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsy5qb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:meh" /></template>
