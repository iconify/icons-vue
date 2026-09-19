<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvwalmfdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mvwalmfdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:rdio-with-circle" /></template>
