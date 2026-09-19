<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8hy7ukcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8hy7ukcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:message-alert-solid" /></template>
