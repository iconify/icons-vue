<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr8r8gbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr8r8gbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nuxt" /></template>
