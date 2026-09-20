<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpw-9zl2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vpw-9zl2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-share" /></template>
