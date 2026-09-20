<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7j9fhbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7j9fhbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:star-line" /></template>
