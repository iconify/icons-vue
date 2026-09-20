<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-r1m6bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-r1m6bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wordpress-logo-2-block" /></template>
