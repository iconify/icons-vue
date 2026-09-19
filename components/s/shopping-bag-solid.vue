<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vly36pbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vly36pbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shopping-bag-solid" /></template>
