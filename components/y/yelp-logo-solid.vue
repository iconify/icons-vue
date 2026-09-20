<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpg043bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cpg043bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:yelp-logo-solid" /></template>
