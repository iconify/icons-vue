<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s38-92b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s38-92b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:socks" /></template>
