<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz4shsbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz4shsbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moonbase" /></template>
