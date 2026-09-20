<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcqslb6ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcqslb6ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tint-slash-solid" /></template>
