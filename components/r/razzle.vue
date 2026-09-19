<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlolbtbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":403,"height":512};
const content = `<path class="hlolbtbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:razzle" /></template>
