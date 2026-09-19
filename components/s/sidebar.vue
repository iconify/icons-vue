<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akupaz0oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akupaz0oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sidebar" /></template>
