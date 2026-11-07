<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9h39ibto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9h39ibto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-2-outline" /></template>
