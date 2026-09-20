<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubngjl5un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ubngjl5un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:store-outline" /></template>
