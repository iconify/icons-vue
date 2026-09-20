<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5y08lpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5y08lpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:signature" /></template>
