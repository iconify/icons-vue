<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfq4wgtpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zfq4wgtpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:swagger-wordmark" /></template>
