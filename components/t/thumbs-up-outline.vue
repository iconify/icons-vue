<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viienxc_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viienxc_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thumbs-up-outline" /></template>
