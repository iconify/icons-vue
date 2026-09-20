<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol_ue80zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_ue80zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-up" /></template>
