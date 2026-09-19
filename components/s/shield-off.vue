<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-ijm78y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps-ijm78y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:shield-off" /></template>
