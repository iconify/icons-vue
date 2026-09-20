<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7392y92n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7392y92n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:telescope-off" /></template>
