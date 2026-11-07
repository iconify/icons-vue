<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkkez7bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkkez7bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-round-broken" /></template>
