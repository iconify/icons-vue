<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu32kswkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu32kswkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind-5s" /></template>
