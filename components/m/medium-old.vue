<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwlh7mskr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwlh7mskr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:medium-old" /></template>
