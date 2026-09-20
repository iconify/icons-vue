<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owjpa7hfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owjpa7hfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mask" /></template>
