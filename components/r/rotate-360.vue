<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-3q5aboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3q5aboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:rotate-360" /></template>
