<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gny9m6b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gny9m6b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:push-chevron-down" /></template>
