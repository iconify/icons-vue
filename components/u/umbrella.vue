<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyxb-y9is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cyxb-y9is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:umbrella" /></template>
