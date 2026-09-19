<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcynyx-7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcynyx-7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-alert" /></template>
