<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nozmsb7hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nozmsb7hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:preview" /></template>
