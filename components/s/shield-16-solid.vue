<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyf44c-ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fyf44c-ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-16-solid" /></template>
