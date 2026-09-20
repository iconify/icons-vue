<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4wmi9bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4wmi9bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitter-line" /></template>
