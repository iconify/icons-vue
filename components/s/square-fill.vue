<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njks3in5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="njks3in5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-fill" /></template>
