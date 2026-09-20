<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3kgh-b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3kgh-b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:twitter-alt" /></template>
