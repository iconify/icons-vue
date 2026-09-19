<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui7et3t-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ui7et3t-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:notification-fill" /></template>
