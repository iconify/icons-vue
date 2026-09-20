<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv4r938lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv4r938lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stop-sharp-fill" /></template>
