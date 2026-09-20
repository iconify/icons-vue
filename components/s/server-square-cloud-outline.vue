<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlx_-9b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlx_-9b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-square-cloud-outline" /></template>
