<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbwr5ownf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbwr5ownf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-sent-01" /></template>
