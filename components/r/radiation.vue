<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi-m936h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmi-m936h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:radiation" /></template>
