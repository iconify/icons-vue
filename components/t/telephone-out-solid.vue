<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-2vgez0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2vgez0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-out-solid" /></template>
