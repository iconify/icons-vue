<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbw1h3bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbw1h3bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:subway" /></template>
