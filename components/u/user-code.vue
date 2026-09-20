<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw6v8tb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw6v8tb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-code" /></template>
