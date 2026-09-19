<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnfa_fb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnfa_fb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-light" /></template>
