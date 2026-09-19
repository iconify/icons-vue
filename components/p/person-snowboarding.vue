<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l71al9aji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l71al9aji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-snowboarding" /></template>
