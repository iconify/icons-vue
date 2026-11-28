<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tas1uj8qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tas1uj8qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-heart-solid" /></template>
