<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-k8dbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kj-k8dbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-double-alt-arrow-up-bold" /></template>
