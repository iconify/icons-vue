<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad4la_mph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad4la_mph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:rocket" /></template>
