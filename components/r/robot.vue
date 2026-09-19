<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7olm2c0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="w7olm2c0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:robot" /></template>
