<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mybjy9i_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mybjy9i_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:success" /></template>
