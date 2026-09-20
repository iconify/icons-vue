<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnn_le0bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn_le0bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:smiley-grin-24" /></template>
