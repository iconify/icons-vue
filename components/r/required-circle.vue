<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_6pobhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh_6pobhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:required-circle" /></template>
