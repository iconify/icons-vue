<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b71j5xfyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b71j5xfyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-circle-outline" /></template>
