<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2aqz483q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2aqz483q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quantcast" /></template>
