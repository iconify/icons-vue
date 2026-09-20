<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyse68b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyse68b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qnap" /></template>
