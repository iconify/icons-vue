<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9kv82bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y9kv82bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:meta-solid" /></template>
