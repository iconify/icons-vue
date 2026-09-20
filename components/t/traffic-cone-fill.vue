<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts0eawbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts0eawbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:traffic-cone-fill" /></template>
