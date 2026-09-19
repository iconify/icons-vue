<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhfgwrg9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":686};
const content = `<path class="rhfgwrg9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:photo" /></template>
