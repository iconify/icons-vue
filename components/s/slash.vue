<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8epdtb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8epdtb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:slash" /></template>
