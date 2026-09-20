<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dih82-bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":290,"height":79};
const content = `<path clip-rule="evenodd" class="dih82-bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:polygon-io-dark" /></template>
