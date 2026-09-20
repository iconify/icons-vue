<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4po6evfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4po6evfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pen-nib-fill" /></template>
