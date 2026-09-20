<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw3edznub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":12};
const content = `<path class="kw3edznub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reflex-dark" /></template>
