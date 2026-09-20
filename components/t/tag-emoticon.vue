<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdya3zb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdya3zb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-emoticon" /></template>
