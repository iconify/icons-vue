<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbhhheven.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbhhheven"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:video" /></template>
