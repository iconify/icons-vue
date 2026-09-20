<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j779_gb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="j779_gb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pause" /></template>
