<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcb9t62hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcb9t62hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:spinner-dotted" /></template>
