<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdj-zf05d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdj-zf05d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:tag-solid" /></template>
