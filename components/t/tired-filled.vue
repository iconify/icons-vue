<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd0o4zbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd0o4zbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tired-filled" /></template>
