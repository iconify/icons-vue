<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duz33rb7u.css';
import '../../css/l/l2_ygdb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duz33rb7u"/><path class="l2_ygdb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tv-bold" /></template>
