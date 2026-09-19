<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp388_vra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zp388_vra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareback" /></template>
