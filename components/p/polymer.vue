<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md3z0jeoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md3z0jeoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:polymer" /></template>
