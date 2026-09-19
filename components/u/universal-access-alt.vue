<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrgf_rbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrgf_rbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:universal-access-alt" /></template>
