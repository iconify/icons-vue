<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csb45tgkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="csb45tgkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-amount-down-alt-solid" /></template>
