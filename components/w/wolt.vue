<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3alqhbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":154,"height":56};
const content = `<path class="b3alqhbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wolt" /></template>
