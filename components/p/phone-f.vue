<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyte-2bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-1.5};
const content = `<path class="pyte-2bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:phone-f" /></template>
