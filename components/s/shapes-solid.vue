<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk_e4zb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_e4zb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shapes-solid" /></template>
