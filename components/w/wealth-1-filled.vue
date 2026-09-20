<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad3rgxbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3rgxbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wealth-1-filled" /></template>
