<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_c__fxxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_c__fxxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twitch-alt" /></template>
