<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt_flyf0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_flyf0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pause-octagon-outline" /></template>
