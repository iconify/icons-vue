<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j96q__hzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j96q__hzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:slippers-one" /></template>
