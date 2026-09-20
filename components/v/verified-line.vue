<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrnix4hzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrnix4hzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:verified-line" /></template>
