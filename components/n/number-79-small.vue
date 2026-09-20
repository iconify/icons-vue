<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmpsdxoqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmpsdxoqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-79-small" /></template>
