<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfj9j6blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfj9j6blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mcb" /></template>
