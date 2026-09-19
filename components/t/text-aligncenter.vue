<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta2un9b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ta2un9b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-aligncenter" /></template>
