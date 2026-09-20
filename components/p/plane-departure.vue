<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnwaqn2lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnwaqn2lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-departure" /></template>
