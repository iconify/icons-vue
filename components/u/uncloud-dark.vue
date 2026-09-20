<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of7jgjbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="of7jgjbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uncloud-dark" /></template>
