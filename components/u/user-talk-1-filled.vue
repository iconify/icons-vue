<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fup7tzn3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fup7tzn3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-talk-1-filled" /></template>
