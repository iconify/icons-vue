<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t04kw_bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t04kw_bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:reply-solid" /></template>
