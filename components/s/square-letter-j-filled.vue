<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvdjg_nud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvdjg_nud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-j-filled" /></template>
