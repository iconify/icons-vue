<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv8_vibzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sv8_vibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:play" /></template>
