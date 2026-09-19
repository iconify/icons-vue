<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viyk3hb3u.css';
import '../../css/r/rqvdmjbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="viyk3hb3u"/><path class="rqvdmjbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-session" /></template>
