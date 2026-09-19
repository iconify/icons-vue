<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-y9tc24r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-y9tc24r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:store-fill" /></template>
