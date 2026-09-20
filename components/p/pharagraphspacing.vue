<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3-vpb73p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3-vpb73p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pharagraphspacing" /></template>
