<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfmcxfo2r.css';
import '../../css/r/rt4k2lbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfmcxfo2r"/><path class="rt4k2lbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:receipt" /></template>
