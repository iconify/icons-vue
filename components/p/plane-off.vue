<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8-alhb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-alhb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-off" /></template>
