<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpnsiq96y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpnsiq96y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:skip-forward" /></template>
