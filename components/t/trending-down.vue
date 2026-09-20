<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdw3bhb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdw3bhb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:trending-down" /></template>
