<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xom7cn-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xom7cn-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-plus" /></template>
