<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezus5bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dezus5bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:text-align-justify" /></template>
