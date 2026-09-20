<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh_k1ybej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh_k1ybej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-off" /></template>
