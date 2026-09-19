<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz39olz5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="pz39olz5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:server" /></template>
