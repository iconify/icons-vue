<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyjqt4buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gyjqt4buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:taobao" /></template>
