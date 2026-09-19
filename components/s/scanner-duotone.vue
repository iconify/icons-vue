<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjvwm7b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjvwm7b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:scanner-duotone" /></template>
