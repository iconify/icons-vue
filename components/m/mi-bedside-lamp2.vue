<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts2nofb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts2nofb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mi-bedside-lamp2" /></template>
