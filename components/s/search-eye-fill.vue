<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfh-7gbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfh-7gbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-eye-fill" /></template>
