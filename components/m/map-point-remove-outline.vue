<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_i_w5qms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_i_w5qms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-remove-outline" /></template>
