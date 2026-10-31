<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyazd6i6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyazd6i6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-right-gloss" /></template>
