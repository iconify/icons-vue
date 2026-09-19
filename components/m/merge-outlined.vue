<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5-xr9bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5-xr9bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:merge-outlined" /></template>
