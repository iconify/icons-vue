<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9zi6020g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9zi6020g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-horizontal-outline" /></template>
