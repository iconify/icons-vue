<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq9psoxhe.css';
import '../../css/u/uzllidbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq9psoxhe"/><path class="uzllidbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-outline" /></template>
