<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/delikcbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="delikcbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sign-right-filled" /></template>
