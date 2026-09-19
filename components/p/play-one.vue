<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nclcvn-dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nclcvn-dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:play-one" /></template>
