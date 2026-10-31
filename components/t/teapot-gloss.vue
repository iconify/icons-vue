<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht8rls_ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht8rls_ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:teapot-gloss" /></template>
