<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b80ez7bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b80ez7bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reptile" /></template>
