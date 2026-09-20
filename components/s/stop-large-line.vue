<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5qazubxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5qazubxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stop-large-line" /></template>
