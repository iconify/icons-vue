<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4r__bbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4r__bbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:reply-all-solid" /></template>
