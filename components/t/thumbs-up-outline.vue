<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppwiyuuhj.css';
import '../../css/g/gdr7v9b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppwiyuuhj"/><path class="gdr7v9b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbs-up-outline" /></template>
