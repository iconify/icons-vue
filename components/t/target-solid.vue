<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz_gphbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz_gphbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:target-solid" /></template>
