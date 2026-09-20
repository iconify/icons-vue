<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyx1q5bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyx1q5bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pexels" /></template>
