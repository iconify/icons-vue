<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkag532vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="dkag532vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:universal-access" /></template>
