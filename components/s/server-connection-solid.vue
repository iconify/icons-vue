<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9mz3ibbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9mz3ibbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:server-connection-solid" /></template>
