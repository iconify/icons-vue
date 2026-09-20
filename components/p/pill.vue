<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjwd1dbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjwd1dbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pill" /></template>
