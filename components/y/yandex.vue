<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmh10nt-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="zmh10nt-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:yandex" /></template>
