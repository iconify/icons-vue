<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss5a9poia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss5a9poia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-settings" /></template>
