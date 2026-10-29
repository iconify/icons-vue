<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prxt5acnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prxt5acnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stop" /></template>
