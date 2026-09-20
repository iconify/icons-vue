<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v08tzf_qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v08tzf_qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ublockorigin" /></template>
