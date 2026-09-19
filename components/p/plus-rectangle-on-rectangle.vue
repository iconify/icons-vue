<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv912ko5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fv912ko5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-rectangle-on-rectangle" /></template>
