<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbxmv9bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxmv9bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-upload-fill-round" /></template>
