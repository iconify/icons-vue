<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2q6ifblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2q6ifblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-group-03" /></template>
