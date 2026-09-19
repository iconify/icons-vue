<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2vpy-vhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":771};
const content = `<path class="v2vpy-vhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:webinsta" /></template>
