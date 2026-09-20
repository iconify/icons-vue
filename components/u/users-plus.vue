<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na-hv6n7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na-hv6n7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-plus" /></template>
