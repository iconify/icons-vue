<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq8hlouil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xq8hlouil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:zzz" /></template>
