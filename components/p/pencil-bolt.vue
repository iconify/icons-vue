<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihnb7ebwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihnb7ebwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-bolt" /></template>
