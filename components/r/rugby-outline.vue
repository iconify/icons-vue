<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btd8tbbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btd8tbbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rugby-outline" /></template>
