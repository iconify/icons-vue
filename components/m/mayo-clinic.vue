<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug37mwq9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ug37mwq9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mayo-clinic" /></template>
