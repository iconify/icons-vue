<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnlx58bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":491,"height":512};
const content = `<path class="hnlx58bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tern" /></template>
