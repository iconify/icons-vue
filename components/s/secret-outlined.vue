<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsg0_d1gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsg0_d1gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:secret-outlined" /></template>
