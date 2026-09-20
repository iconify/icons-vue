<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lddgidbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lddgidbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:volume-2" /></template>
