<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y36z6v4nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y36z6v4nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mainsail" /></template>
