<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbdr5abve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zbdr5abve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:tumblr" /></template>
