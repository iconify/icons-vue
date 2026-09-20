<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aap8i-4xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aap8i-4xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-outline" /></template>
