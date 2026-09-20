<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl3o0g27x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl3o0g27x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sunrise" /></template>
