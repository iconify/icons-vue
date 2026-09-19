<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn-2ng51c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nn-2ng51c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:text-document" /></template>
