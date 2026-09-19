<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8v1f0hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bg8v1f0hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:upload-to-cloud" /></template>
