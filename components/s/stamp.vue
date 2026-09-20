<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mglmu62iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mglmu62iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:stamp" /></template>
