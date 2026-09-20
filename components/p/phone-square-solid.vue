<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf49cdg9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kf49cdg9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone-square-solid" /></template>
