<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su5hedbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="su5hedbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-badge-plus" /></template>
