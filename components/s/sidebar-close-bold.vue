<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojtd7k2go.css';
import '../../css/d/dkbffkbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojtd7k2go"/><path class="dkbffkbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-close-bold" /></template>
