<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3q-8-ppq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m3q-8-ppq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:staylinked" /></template>
