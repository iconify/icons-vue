<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxt6upcmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxt6upcmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sailboat" /></template>
