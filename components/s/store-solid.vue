<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oot7aachb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oot7aachb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:store-solid" /></template>
