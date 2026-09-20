<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1v1pfb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1v1pfb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-right-bottom-fill" /></template>
