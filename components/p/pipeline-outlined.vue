<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y459gbbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y459gbbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:pipeline-outlined" /></template>
