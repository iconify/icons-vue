<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkjgbnxno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkjgbnxno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:snowy-fill" /></template>
