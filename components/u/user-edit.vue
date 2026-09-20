<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvvqs2vlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvvqs2vlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-edit" /></template>
