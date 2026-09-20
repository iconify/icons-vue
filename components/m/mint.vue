<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srkv66j6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srkv66j6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mint" /></template>
