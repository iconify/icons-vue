<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6wdq4byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z6wdq4byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag-filled" /></template>
