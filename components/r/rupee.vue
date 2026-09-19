<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb081djxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb081djxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rupee" /></template>
