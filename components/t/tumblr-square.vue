<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_2eiab_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_2eiab_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tumblr-square" /></template>
