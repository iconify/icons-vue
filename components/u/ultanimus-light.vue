<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s77gngb9u.css';
import '../../css/n/n3-u1ki8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":20,"left":3,"top":2};
const content = `<path class="s77gngb9u"/><circle class="n3-u1ki8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ultanimus-light" /></template>
