<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_8bqzb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_8bqzb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tripadvisor-logo-bold" /></template>
