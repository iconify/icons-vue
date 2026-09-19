<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-th0bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1-th0bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-normal-fill" /></template>
