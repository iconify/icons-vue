<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsbnyev8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsbnyev8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:power-solid" /></template>
