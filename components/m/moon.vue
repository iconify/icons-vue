<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhlyw1b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhlyw1b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:moon" /></template>
