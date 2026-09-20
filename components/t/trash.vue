<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x09f78b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x09f78b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:trash" /></template>
