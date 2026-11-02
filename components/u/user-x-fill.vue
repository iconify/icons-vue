<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak6hi0bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6hi0bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-x-fill" /></template>
