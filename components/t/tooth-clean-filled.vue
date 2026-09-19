<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boimr8fff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="boimr8fff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-clean-filled" /></template>
