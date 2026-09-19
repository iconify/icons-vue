<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tprbt3btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tprbt3btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:viewfinder-circle" /></template>
