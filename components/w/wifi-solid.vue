<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwpti4c9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pwpti4c9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wifi-solid" /></template>
