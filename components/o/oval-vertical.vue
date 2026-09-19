<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn4s_ps8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4s_ps8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:oval-vertical" /></template>
