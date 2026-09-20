<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9bg9h1um.css';
import '../../css/t/txkp30byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9bg9h1um"/><path class="txkp30byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sfund" /></template>
