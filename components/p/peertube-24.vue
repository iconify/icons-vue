<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acs_d8b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acs_d8b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:peertube-24" /></template>
