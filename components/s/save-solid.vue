<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdiyfl2-s.css';
import '../../css/d/d_sq5jfqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdiyfl2-s"/><path class="d_sq5jfqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:save-solid" /></template>
