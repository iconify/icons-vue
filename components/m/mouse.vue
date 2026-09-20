<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfy74gbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xfy74gbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:mouse" /></template>
