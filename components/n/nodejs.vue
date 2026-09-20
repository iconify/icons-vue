<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0fl3byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br0fl3byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:nodejs" /></template>
