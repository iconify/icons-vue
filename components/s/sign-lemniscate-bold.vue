<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtv6wdbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtv6wdbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-lemniscate-bold" /></template>
