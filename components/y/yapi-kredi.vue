<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceemambxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1548,"height":786};
const content = `<path class="ceemambxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yapi-kredi" /></template>
