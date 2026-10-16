<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq-whqbyl.css';
import '../../css/n/nsw7x4gvs.css';
import '../../css/e/epapbpbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zq-whqbyl"/><path class="nsw7x4gvs"/><path class="epapbpbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pg-back-web-light" /></template>
