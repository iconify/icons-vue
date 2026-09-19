<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnbntv8lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":685,"height":717};
const content = `<path class="hnbntv8lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sns" /></template>
