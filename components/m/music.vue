<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah-qa3bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah-qa3bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:music" /></template>
