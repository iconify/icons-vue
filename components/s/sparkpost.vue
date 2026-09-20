<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5pc9gbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5pc9gbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sparkpost" /></template>
