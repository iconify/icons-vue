<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy_bfjbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy_bfjbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:wikipedia" /></template>
