<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8p1fxbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8p1fxbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shapes-alt-2" /></template>
