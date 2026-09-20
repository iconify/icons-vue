<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5y_5b-4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5y_5b-4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:streamlabs" /></template>
