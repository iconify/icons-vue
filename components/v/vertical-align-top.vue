<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk-1c2b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-1c2b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vertical-align-top" /></template>
