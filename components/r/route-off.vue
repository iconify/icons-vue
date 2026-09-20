<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg5zy3b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5zy3b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:route-off" /></template>
