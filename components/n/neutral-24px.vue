<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj4ohyv-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4ohyv-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:neutral-24px" /></template>
