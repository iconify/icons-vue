<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx3sw6b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx3sw6b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:pencil-alt" /></template>
