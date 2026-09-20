<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd7pgj9zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd7pgj9zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stream-solid" /></template>
