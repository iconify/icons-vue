<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjndzv7wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjndzv7wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-outline" /></template>
