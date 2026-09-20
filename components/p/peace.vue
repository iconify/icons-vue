<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3q9sfm5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3q9sfm5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:peace" /></template>
