<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk2o14bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pk2o14bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:shopping-bag" /></template>
