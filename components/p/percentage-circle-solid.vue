<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2ac1u1rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2ac1u1rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:percentage-circle-solid" /></template>
