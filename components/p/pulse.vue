<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsomblq2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsomblq2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pulse" /></template>
