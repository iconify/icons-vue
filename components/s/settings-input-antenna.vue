<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siwd_6bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siwd_6bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-input-antenna" /></template>
