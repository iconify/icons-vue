<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu06ygb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu06ygb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:moon3" /></template>
