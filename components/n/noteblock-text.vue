<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxlja6bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxlja6bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:noteblock-text" /></template>
