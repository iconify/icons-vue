<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t04w3ucra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t04w3ucra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pause" /></template>
