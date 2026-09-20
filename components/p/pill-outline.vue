<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4gcxpbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4gcxpbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pill-outline" /></template>
