<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0fk7bcqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0fk7bcqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:toyota" /></template>
