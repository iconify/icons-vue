<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkb1lk6xd.css';
import '../../css/e/e5703z3pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkb1lk6xd"/><path class="e5703z3pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:map-pin" /></template>
