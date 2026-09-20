<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alyfqt4-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="alyfqt4-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:unlock" /></template>
