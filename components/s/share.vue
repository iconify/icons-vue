<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik_gqmbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="ik_gqmbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:share" /></template>
