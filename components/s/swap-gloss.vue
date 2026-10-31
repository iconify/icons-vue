<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeivlib5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeivlib5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:swap-gloss" /></template>
