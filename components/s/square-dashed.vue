<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afo9k_fki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afo9k_fki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:square-dashed" /></template>
