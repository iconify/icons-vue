<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-l9nwbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-l9nwbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plug-circle-outline" /></template>
