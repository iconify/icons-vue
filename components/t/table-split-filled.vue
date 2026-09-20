<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovysgutzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovysgutzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:table-split-filled" /></template>
