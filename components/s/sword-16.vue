<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkarxnbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tkarxnbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sword-16" /></template>
