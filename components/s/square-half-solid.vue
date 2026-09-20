<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-sx6ybrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-sx6ybrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-half-solid" /></template>
