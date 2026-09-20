<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a670m2dwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a670m2dwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:unsplash" /></template>
