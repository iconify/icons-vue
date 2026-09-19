<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_r8-tbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="x_r8-tbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yandex" /></template>
