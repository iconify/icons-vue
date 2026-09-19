<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avjkpk4pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avjkpk4pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:snail" /></template>
