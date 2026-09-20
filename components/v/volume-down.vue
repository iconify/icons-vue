<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nny3q-ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="nny3q-ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-down" /></template>
