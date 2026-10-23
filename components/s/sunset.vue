<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq0w-2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq0w-2bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sunset" /></template>
