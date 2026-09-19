<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsy7k0alc.css';
import '../../css/z/zt-51hcly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsy7k0alc"/><path class="zt-51hcly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meteor" /></template>
