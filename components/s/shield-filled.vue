<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wij2urb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wij2urb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-filled" /></template>
