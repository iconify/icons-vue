<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn8zd61qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn8zd61qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-coordinate-filled" /></template>
