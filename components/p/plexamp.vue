<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7h-_pb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7h-_pb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:plexamp" /></template>
