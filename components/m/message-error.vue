<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou99_sb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou99_sb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-error" /></template>
