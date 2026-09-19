<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgy4hvbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kgy4hvbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-numeric-down-alt" /></template>
