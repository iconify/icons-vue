<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woc2qorbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woc2qorbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-filled" /></template>
