<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kinrn02eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kinrn02eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-5-filled" /></template>
