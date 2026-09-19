<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg-t2ccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gg-t2ccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sendtoback" /></template>
