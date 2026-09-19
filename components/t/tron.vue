<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afm2-tblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="afm2-tblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tron" /></template>
