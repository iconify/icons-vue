<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdq6q2bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdq6q2bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:x-octagon" /></template>
