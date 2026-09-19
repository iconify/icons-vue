<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g22774ouw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g22774ouw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:toggle-on-solid" /></template>
