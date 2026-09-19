<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szppspbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1408};
const content = `<path class="szppspbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mixcloud" /></template>
