<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynw-okwdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ynw-okwdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:sun" /></template>
