<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5syhb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn5syhb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play" /></template>
