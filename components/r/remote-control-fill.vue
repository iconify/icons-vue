<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk_n9jbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_n9jbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remote-control-fill" /></template>
