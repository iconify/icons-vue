<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzshn-b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzshn-b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-hood" /></template>
