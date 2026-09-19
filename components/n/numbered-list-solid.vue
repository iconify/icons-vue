<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn4kzqjcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sn4kzqjcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:numbered-list-solid" /></template>
