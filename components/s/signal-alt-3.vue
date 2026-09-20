<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eerdskcco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eerdskcco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:signal-alt-3" /></template>
