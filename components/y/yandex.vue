<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh7glrryi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yh7glrryi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:yandex" /></template>
