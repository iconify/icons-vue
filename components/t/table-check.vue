<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayx7sbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uayx7sbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-check" /></template>
