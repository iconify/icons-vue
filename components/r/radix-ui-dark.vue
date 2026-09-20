<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0_tdbckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":25,"left":4};
const content = `<path class="w0_tdbckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:radix-ui-dark" /></template>
