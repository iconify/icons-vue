<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afjbk-grt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afjbk-grt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-delete-outline" /></template>
