<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv8lmcxko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv8lmcxko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thumbs-up" /></template>
