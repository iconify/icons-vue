<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_0r-v9zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i_0r-v9zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tornado" /></template>
