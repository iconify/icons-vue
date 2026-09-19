<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfbn8ab0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfbn8ab0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:notification-solid" /></template>
