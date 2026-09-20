<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxst_t7um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxst_t7um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sphinx" /></template>
