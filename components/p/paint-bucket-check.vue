<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at31kobgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at31kobgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paint-bucket-check" /></template>
