<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l14-q-b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l14-q-b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:male" /></template>
