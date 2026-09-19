<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfucfob_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yfucfob_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:trash-alt" /></template>
