<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9hu36b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9hu36b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:map-fold-solid" /></template>
