<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z68h5ubme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z68h5ubme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:volume-4" /></template>
