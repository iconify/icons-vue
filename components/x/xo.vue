<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7f-rg6_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7f-rg6_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:xo" /></template>
