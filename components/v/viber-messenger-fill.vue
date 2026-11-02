<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv46si9ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv46si9ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:viber-messenger-fill" /></template>
