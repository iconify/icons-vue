<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snsbht43n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snsbht43n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-key" /></template>
