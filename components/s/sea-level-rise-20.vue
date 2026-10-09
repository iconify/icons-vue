<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t15864jur.css';
import '../../css/a/apln4p07a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t15864jur"/><path class="apln4p07a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sea-level-rise-20" /></template>
