<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_r4xdbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_r4xdbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-outline" /></template>
