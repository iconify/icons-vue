<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8cnyjb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8cnyjb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:testcafe" /></template>
