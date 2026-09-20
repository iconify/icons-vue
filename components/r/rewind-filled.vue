<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimrvnb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bimrvnb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind-filled" /></template>
