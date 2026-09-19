<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lix6-_buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lix6-_buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wps-office" /></template>
