<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpg4mpn-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg4mpn-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:server-cluster" /></template>
