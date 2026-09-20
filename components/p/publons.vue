<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exwyr5jvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exwyr5jvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:publons" /></template>
