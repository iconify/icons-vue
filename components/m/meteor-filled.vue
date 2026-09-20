<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy8owwblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy8owwblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:meteor-filled" /></template>
