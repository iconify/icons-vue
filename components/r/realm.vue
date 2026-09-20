<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiqt0cbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqt0cbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:realm" /></template>
