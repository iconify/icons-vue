<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br41wibdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="br41wibdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:toilet-sign-man" /></template>
