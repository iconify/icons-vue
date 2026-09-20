<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaazzmbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaazzmbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:thumbs-up-fill" /></template>
