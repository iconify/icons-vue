<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iis8z6o6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iis8z6o6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nextdns" /></template>
