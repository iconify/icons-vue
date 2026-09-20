<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb7lxbc2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb7lxbc2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:star" /></template>
