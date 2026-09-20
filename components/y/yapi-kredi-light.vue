<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os7-1hbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1548,"height":786};
const content = `<path class="os7-1hbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yapi-kredi-light" /></template>
