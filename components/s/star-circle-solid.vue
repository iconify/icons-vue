<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7zbev1jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f7zbev1jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:star-circle-solid" /></template>
