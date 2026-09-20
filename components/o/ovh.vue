<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdf0grb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdf0grb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ovh" /></template>
