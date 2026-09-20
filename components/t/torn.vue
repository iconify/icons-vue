<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3af1bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hr3af1bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:torn" /></template>
