<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ionisxb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ionisxb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-hotdog" /></template>
