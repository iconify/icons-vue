<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alobnivwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1548,"height":786};
const content = `<path class="alobnivwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yapi-kredi-dark" /></template>
