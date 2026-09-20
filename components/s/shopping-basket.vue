<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uml9d-m-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="uml9d-m-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:shopping-basket" /></template>
