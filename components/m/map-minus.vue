<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyj3zdbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyj3zdbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-minus" /></template>
