<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_o9xqbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_o9xqbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:underline" /></template>
