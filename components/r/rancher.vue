<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rawz8tvsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rawz8tvsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rancher" /></template>
