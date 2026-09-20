<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmrki3njp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmrki3njp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-outline" /></template>
