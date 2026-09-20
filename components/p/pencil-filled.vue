<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqd6l4b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqd6l4b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-filled" /></template>
