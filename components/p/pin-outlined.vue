<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7u5rm1fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7u5rm1fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:pin-outlined" /></template>
