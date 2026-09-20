<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if49zsb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="if49zsb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:printer" /></template>
