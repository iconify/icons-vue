<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz9n6kbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kz9n6kbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tablet-capsule-solid" /></template>
