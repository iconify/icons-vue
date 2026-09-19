<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipfks6n4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ipfks6n4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:t-bubble" /></template>
