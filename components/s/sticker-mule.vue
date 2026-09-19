<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvge0qb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lvge0qb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:sticker-mule" /></template>
