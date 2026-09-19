<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ybdmbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":488};
const content = `<path class="p7ybdmbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:twitter" /></template>
