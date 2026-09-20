<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2mt62b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2mt62b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunset-2" /></template>
