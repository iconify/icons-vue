<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppv6zu5ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppv6zu5ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-seven-circle" /></template>
