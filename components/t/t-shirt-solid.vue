<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kse3elb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kse3elb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:t-shirt-solid" /></template>
