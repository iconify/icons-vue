<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahocycbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ahocycbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:zip-file-outline" /></template>
