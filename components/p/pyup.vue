<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcyxmuqez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":443,"height":512};
const content = `<path class="zcyxmuqez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pyup" /></template>
