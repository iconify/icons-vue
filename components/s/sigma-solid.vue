<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v03-aihml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v03-aihml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sigma-solid" /></template>
