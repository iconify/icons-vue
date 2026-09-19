<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb6y63g1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xb6y63g1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:minus-circle-solid" /></template>
