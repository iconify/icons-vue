<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sprf0kjfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sprf0kjfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:menu-gloss" /></template>
