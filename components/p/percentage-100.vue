<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0e_tfj0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0e_tfj0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:percentage-100" /></template>
