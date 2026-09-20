<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv96-jbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv96-jbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ntfy" /></template>
