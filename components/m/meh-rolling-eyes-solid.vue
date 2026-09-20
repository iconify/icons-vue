<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6urbrbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z6urbrbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:meh-rolling-eyes-solid" /></template>
