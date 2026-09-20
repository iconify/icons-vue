<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_v1athia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_v1athia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yandex" /></template>
