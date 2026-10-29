<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuy1aab-e.css';
import '../../css/k/keh7f8wkw.css';
import '../../css/i/ikwvq7b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuy1aab-e wm-k"/><path class="keh7f8wkw wm-a"/><path class="ikwvq7b1d wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shopping-cart" /></template>
