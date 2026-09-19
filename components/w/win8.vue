<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_1hrz-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":986,"height":1000};
const content = `<path class="ii_1hrz-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:win8" /></template>
