<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6gx6-b_c.css';
import '../../css/z/z6xyxkbfa.css';
import '../../css/u/u_isrfbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6gx6-b_c"/><path clip-rule="evenodd" class="z6xyxkbfa"/><path class="u_isrfbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:treadmill-round-bold" /></template>
