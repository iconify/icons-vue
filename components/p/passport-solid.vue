<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lld8wpyib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lld8wpyib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:passport-solid" /></template>
