<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe03g2-dk.css';
import '../../css/i/igs44wb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe03g2-dk"/><path class="igs44wb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wink-tongue" /></template>
