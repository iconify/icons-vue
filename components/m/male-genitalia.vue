<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boa45ibjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="boa45ibjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:male-genitalia" /></template>
