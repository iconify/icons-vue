<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2s3sqbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s3sqbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-exclamation" /></template>
