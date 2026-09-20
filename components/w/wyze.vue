<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl6niib_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl6niib_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wyze" /></template>
