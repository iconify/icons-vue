<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psn7qac5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psn7qac5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-silence" /></template>
